<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znipc8brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znipc8brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:home" /></template>
