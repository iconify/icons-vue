<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7b1sbc0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7b1sbc0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cube" /></template>
