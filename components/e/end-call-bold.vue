<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh6grdblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh6grdblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-bold" /></template>
