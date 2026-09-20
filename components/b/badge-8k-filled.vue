<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp-67djaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp-67djaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badge-8k-filled" /></template>
