<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii_o2hbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ii_o2hbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:accent-dark" /></template>
