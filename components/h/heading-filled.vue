<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf_-mlbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf_-mlbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heading-filled" /></template>
