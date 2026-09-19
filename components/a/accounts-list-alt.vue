<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3muasauf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="n3muasauf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:accounts-list-alt" /></template>
