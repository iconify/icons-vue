<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u96qf2b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u96qf2b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-left-justified" /></template>
