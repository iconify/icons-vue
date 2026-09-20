<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgdm3ebfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="xgdm3ebfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-all-direction" /></template>
