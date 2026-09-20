<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw-90wbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw-90wbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-k-filled" /></template>
