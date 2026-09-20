<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6lgoib4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6lgoib4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:command-line-filled" /></template>
