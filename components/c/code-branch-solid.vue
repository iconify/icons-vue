<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uegh43x7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uegh43x7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:code-branch-solid" /></template>
