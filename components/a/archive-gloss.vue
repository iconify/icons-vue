<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yth53kq-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yth53kq-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:archive-gloss" /></template>
