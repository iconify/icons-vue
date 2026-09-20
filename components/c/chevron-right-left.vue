<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xznmscbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xznmscbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-right-left" /></template>
