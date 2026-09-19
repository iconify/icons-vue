<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8ude0bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="m8ude0bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:chevron-up" /></template>
