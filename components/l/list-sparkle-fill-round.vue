<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki-dbhbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki-dbhbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-sparkle-fill-round" /></template>
