<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4hz1de1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f4hz1de1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:collection" /></template>
