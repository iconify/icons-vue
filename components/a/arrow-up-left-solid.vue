<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh8d11bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh8d11bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-left-solid" /></template>
