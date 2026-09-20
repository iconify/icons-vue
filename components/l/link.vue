<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_h9hlbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-3};
const content = `<path class="c_h9hlbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:link" /></template>
