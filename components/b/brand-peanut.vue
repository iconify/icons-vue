<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlex6fahs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlex6fahs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-peanut" /></template>
