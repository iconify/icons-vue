<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w315ns-nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w315ns-nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lighthouse" /></template>
