<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q192h5cgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="q192h5cgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:forestalt" /></template>
