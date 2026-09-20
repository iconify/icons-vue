<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g76-_3dup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g76-_3dup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:freebsd" /></template>
