<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhgvwmz6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhgvwmz6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-tenge" /></template>
