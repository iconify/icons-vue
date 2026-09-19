<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyd6mobsh.css';
import '../../css/s/sv7nt6skj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyd6mobsh"/><path class="sv7nt6skj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:export" /></template>
