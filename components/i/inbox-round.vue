<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj2qkhw1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj2qkhw1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-round" /></template>
