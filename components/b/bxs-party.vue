<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7auwxbuh.css';
import '../../css/b/bw3v4wb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7auwxbuh"/><path class="bw3v4wb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-party" /></template>
