<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwl3inblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dwl3inblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coffer-dark" /></template>
