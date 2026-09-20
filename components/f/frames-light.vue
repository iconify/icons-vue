<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfvac11yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tfvac11yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frames-light" /></template>
