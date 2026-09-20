<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssww8xbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ssww8xbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:lineicons-symbol-alt-2" /></template>
