<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up6bcgbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up6bcgbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-paypal" /></template>
