<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo4v4hbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="oo4v4hbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-up-on-square-stack" /></template>
