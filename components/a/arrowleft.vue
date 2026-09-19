<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0lsn2zoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1026};
const content = `<path class="n0lsn2zoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:arrowleft" /></template>
