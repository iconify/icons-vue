<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myyxy-blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myyxy-blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-move-up-filled" /></template>
