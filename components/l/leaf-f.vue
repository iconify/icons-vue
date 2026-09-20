<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_yy9nbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3.5,"top":-1};
const content = `<path class="f_yy9nbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:leaf-f" /></template>
