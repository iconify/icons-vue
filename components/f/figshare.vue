<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfkd-0bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfkd-0bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:figshare" /></template>
