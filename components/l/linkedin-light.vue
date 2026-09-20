<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho4qtziaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ho4qtziaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkedin-light" /></template>
