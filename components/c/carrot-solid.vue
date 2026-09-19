<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj0z13bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj0z13bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:carrot-solid" /></template>
