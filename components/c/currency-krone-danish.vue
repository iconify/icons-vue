<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5aimq4hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5aimq4hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-krone-danish" /></template>
