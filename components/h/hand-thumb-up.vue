<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbl7lh2ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gbl7lh2ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:hand-thumb-up" /></template>
