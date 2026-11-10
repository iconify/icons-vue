<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nazm3dbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nazm3dbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-exclamation" /></template>
