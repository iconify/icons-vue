<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow1w-gj-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow1w-gj-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lungs-filled" /></template>
