<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv4bgxz2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv4bgxz2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:folder-slash" /></template>
