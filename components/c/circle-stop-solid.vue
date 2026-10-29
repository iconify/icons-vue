<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk0giub_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk0giub_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-stop-solid" /></template>
