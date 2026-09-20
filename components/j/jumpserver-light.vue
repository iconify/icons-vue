<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2mi4d5uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2mi4d5uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jumpserver-light" /></template>
