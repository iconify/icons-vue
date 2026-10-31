<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egmb52bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egmb52bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-stop-round" /></template>
