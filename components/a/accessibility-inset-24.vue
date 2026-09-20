<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm9g3ydmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm9g3ydmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:accessibility-inset-24" /></template>
