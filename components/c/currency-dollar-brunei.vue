<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq9mwsb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq9mwsb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-dollar-brunei" /></template>
