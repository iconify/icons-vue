<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku1ngabxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ku1ngabxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:facebook-logo" /></template>
