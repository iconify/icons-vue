<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y39j1xb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4.5};
const content = `<path class="y39j1xb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:digg" /></template>
