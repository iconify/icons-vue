<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc2sj5asw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc2sj5asw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-5-fill" /></template>
