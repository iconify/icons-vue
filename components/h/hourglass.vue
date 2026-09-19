<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea64zqbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea64zqbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:hourglass" /></template>
