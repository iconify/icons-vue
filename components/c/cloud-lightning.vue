<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6vexmbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6vexmbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cloud-lightning" /></template>
