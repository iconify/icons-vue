<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh-qt9rta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh-qt9rta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-x" /></template>
