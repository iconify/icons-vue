<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwl57ubde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary xwl57ubde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fit-width-duotone" /></template>
