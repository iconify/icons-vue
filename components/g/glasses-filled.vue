<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq-lf_6bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq-lf_6bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:glasses-filled" /></template>
