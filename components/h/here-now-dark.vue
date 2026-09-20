<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdtt5t4xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pdtt5t4xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:here-now-dark" /></template>
