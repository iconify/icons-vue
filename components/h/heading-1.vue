<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgu6i8a0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgu6i8a0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:heading-1" /></template>
