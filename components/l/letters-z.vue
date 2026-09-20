<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_x9f2kmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_x9f2kmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-z" /></template>
