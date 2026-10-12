<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwnhtl0tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwnhtl0tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:aspire" /></template>
