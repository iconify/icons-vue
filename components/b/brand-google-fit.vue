<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1t8_n4gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1t8_n4gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-google-fit" /></template>
