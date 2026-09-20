<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_qj0utvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_qj0utvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-vertical" /></template>
