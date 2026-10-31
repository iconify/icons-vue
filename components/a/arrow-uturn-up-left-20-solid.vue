<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8n6e4yxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x8n6e4yxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-up-left-20-solid" /></template>
