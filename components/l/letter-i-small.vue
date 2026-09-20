<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giho2bore.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giho2bore"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-i-small" /></template>
