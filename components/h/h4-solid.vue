<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg0vacvyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zg0vacvyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h4-solid" /></template>
