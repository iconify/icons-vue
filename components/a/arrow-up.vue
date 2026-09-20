<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_x1-jbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-4.5};
const content = `<path class="t_x1-jbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrow-up" /></template>
