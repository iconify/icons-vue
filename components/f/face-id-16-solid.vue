<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8defhbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l8defhbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-id-16-solid" /></template>
