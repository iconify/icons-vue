<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_4kpbots.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_4kpbots"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-octagon" /></template>
