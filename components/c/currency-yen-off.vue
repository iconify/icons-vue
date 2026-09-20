<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi7c6csqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi7c6csqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-yen-off" /></template>
