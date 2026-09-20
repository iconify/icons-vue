<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emqxlxbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emqxlxbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-2-filled" /></template>
