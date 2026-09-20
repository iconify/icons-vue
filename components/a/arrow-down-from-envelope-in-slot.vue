<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb9a57b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wb9a57b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down-from-envelope-in-slot" /></template>
