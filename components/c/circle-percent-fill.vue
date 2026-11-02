<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5589jwrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5589jwrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-percent-fill" /></template>
