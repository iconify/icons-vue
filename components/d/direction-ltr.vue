<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l77vd0brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="l77vd0brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:direction-ltr" /></template>
