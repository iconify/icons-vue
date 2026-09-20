<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_v6015-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_v6015-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:expand-more-duotone" /></template>
