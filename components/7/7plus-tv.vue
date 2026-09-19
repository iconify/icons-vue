<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc_2e-b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc_2e-b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:7plus-tv" /></template>
