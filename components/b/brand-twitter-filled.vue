<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa9yf7bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa9yf7bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-twitter-filled" /></template>
