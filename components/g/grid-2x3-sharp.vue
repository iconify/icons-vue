<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpp4bbb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpp4bbb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x3-sharp" /></template>
