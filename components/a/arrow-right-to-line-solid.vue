<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdgpambfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdgpambfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-right-to-line-solid" /></template>
