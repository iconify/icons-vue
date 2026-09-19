<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5sb79ecg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5sb79ecg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-right" /></template>
