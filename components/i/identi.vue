<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5fehibxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":480};
const content = `<path class="m5fehibxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:identi" /></template>
