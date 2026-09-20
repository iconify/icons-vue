<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-pgxabuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-pgxabuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-x" /></template>
