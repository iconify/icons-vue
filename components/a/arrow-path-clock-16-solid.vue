<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euu_br-wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="euu_br-wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-clock-16-solid" /></template>
