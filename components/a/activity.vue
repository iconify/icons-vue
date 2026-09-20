<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7hdrzavt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7hdrzavt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:activity" /></template>
