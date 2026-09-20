<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9dhk5b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9dhk5b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-b-filled" /></template>
