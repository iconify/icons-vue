<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap_4y_bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ap_4y_bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:heart-small-solid" /></template>
