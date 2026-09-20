<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3wpvxyei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3wpvxyei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-off" /></template>
