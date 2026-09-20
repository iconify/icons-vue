<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxdu6ebxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxdu6ebxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-polymer" /></template>
