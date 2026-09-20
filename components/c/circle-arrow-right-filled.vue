<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmfj55_qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmfj55_qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-arrow-right-filled" /></template>
