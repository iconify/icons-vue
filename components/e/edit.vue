<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trhuiyb4d.css';
import '../../css/j/j_4gibdnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trhuiyb4d"/><path class="j_4gibdnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:edit" /></template>
