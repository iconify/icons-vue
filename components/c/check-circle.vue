<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwkw3-cho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lwkw3-cho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:check-circle" /></template>
