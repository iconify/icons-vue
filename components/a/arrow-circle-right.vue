<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_29c7b-y.css';
import '../../css/p/pvz3l-b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_29c7b-y"/><path class="pvz3l-b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:arrow-circle-right" /></template>
