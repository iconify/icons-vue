<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm83secra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vm83secra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:archive-box-arrow-up-20-solid" /></template>
