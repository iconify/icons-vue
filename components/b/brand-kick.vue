<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koj8yibyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koj8yibyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-kick" /></template>
