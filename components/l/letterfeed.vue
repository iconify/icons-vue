<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl1zvma-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vl1zvma-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:letterfeed" /></template>
