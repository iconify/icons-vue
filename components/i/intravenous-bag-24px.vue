<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp9zlby6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vp9zlby6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:intravenous-bag-24px" /></template>
