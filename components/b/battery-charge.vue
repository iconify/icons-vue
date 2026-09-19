<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk9loab2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":456};
const content = `<path class="pk9loab2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:battery-charge" /></template>
