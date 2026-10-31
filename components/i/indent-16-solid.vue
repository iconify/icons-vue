<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt8_6yb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yt8_6yb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:indent-16-solid" /></template>
