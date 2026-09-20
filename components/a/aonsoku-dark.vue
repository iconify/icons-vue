<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2fjpkz3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2fjpkz3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aonsoku-dark" /></template>
