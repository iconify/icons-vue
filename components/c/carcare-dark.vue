<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgxsjub5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rgxsjub5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:carcare-dark" /></template>
