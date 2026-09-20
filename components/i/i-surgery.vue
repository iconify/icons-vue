<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfuzbjb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gfuzbjb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-surgery" /></template>
