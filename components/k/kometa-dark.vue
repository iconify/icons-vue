<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/womat1bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="womat1bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kometa-dark" /></template>
