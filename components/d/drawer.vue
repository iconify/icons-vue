<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nubud3uip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="nubud3uip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:drawer" /></template>
