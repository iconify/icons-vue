<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geb_t6bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geb_t6bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:jcb-japan-credit-bureau-fill" /></template>
