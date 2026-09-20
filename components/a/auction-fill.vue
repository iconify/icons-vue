<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io3fzsuib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io3fzsuib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:auction-fill" /></template>
