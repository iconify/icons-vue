<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noh0r_b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noh0r_b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-number-2-filled" /></template>
