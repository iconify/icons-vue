<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayml4ibqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayml4ibqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-golfball-e14" /></template>
