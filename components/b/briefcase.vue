<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2p2wut3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j2p2wut3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:briefcase" /></template>
