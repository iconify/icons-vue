<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0srv8qcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0srv8qcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-r-filled" /></template>
