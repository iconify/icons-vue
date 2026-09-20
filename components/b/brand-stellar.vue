<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipeu9ssnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipeu9ssnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-stellar" /></template>
