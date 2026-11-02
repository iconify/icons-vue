<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7rbfubhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7rbfubhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:battery-25" /></template>
