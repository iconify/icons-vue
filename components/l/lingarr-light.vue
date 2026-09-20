<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4oe12p6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o4oe12p6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lingarr-light" /></template>
