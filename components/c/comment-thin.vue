<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqp_n4b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqp_n4b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-thin" /></template>
