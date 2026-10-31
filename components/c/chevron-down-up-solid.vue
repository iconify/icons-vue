<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-i77zbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-i77zbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-down-up-solid" /></template>
