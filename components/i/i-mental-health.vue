<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqfaxx8mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tqfaxx8mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-mental-health" /></template>
