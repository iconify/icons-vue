<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8p-xymns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s8p-xymns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:download" /></template>
