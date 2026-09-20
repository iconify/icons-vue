<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in57ykb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in57ykb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-x-filled" /></template>
