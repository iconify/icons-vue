<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeoe7r16d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeoe7r16d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:credit-card-front" /></template>
