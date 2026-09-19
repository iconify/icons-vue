<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g85vmmbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="g85vmmbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bancircle" /></template>
