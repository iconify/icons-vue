<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irm1bq5fz.css';
import '../../css/w/w9u355bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="irm1bq5fz"/><path class="w9u355bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:globe" /></template>
