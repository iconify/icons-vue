<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_80cab1p.css';
import '../../css/a/aps6ewwol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_80cab1p"/><path class="aps6ewwol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:currency-note-filled" /></template>
