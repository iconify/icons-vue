<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm6notbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm6notbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:check-unread-03" /></template>
