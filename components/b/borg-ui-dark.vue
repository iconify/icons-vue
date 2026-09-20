<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlc72rrtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wlc72rrtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:borg-ui-dark" /></template>
