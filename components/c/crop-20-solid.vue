<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo-4ck05w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qo-4ck05w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crop-20-solid" /></template>
