<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od1i-5lhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="od1i-5lhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ars-technica-light" /></template>
