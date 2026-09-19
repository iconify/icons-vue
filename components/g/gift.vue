<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm6ujac-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mm6ujac-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:gift" /></template>
