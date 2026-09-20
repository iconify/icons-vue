<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aow3f85ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aow3f85ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:capture-filled" /></template>
