<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhm-r8bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hhm-r8bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-arrow-up-20-solid" /></template>
