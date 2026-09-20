<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kft_m6maj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kft_m6maj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-foursquare" /></template>
