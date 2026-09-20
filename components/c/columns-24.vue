<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je2910b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je2910b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:columns-24" /></template>
