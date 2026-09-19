<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc9yycyos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc9yycyos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:camera" /></template>
