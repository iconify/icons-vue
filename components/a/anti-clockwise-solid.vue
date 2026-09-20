<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj4srpnqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kj4srpnqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:anti-clockwise-solid" /></template>
