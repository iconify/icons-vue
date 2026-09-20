<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2t7xm6vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2t7xm6vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:beatport" /></template>
