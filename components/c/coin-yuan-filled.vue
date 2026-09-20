<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfri2cb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfri2cb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:coin-yuan-filled" /></template>
