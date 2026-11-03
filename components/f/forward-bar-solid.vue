<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl7yb5rrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl7yb5rrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:forward-bar-solid" /></template>
