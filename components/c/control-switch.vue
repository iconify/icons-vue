<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm4c2pb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sm4c2pb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:control-switch" /></template>
