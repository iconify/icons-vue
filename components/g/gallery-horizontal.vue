<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w025-gj6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w025-gj6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gallery-horizontal" /></template>
