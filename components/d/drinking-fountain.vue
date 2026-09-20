<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er8u5db2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="er8u5db2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:drinking-fountain" /></template>
