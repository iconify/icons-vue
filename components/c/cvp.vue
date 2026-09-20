<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwk_lb6to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwk_lb6to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cvp" /></template>
