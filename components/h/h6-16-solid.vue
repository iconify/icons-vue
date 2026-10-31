<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve4cdcoma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ve4cdcoma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h6-16-solid" /></template>
