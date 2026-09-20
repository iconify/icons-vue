<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qofpabhan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qofpabhan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:capture-off" /></template>
