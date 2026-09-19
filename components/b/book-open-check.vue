<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebu-7egqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebu-7egqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:book-open-check" /></template>
