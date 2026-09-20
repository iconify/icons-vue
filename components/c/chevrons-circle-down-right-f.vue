<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_04yvq2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="z_04yvq2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-circle-down-right-f" /></template>
