<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_204jbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_204jbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:joplin-dark" /></template>
