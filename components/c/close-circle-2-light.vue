<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-zho3bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-zho3bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-circle-2-light" /></template>
