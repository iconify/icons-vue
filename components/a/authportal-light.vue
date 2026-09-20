<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp-luevbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-luevbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authportal-light" /></template>
