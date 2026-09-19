<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er2fz3ono.css';
import '../../css/l/lwb5t-h6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="er2fz3ono"/><path class="lwb5t-h6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:earth-outline" /></template>
