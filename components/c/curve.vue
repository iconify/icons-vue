<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-2_bsb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-2_bsb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:curve" /></template>
