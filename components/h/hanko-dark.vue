<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctoz3fbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ctoz3fbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hanko-dark" /></template>
