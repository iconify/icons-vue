<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaodx6v3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaodx6v3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-x" /></template>
