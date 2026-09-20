<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqku5tbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqku5tbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:capsule-horizontal-filled" /></template>
