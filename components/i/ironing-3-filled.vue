<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzoxw91en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzoxw91en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ironing-3-filled" /></template>
