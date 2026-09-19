<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3bhk4bbt.css';
import '../../css/f/fuc7qlr2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3bhk4bbt"/><path class="fuc7qlr2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-jpg" /></template>
