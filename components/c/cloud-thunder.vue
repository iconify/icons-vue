<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-g98yz0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="w-g98yz0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:cloud-thunder" /></template>
