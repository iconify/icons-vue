<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y13z0jbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y13z0jbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazoncloudwatch" /></template>
