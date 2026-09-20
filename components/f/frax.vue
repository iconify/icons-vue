<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf12py5gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf12py5gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:frax" /></template>
