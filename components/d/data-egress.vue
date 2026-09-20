<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmciabrma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmciabrma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:data-egress" /></template>
