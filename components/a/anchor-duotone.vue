<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsqizwwgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsqizwwgh primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:anchor-duotone" /></template>
