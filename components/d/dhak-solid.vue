<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcu99wbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcu99wbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dhak-solid" /></template>
