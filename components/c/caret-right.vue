<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_sk32p-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_sk32p-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-right" /></template>
