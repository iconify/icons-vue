<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s24j4orns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s24j4orns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-corn-solid" /></template>
