<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f40rxmbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f40rxmbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alby-hub-dark" /></template>
