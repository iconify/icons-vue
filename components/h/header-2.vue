<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igipjz3oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-7};
const content = `<path class="igipjz3oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:header-2" /></template>
