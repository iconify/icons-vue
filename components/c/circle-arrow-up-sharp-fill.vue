<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-6ptdbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-6ptdbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-up-sharp-fill" /></template>
