<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl6__vdrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl6__vdrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bounce-right" /></template>
