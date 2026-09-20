<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_q25gb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_q25gb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:ellipsis-h" /></template>
