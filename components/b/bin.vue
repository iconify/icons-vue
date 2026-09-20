<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcab0ozmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wcab0ozmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bin" /></template>
