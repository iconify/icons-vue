<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u414_bccf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u414_bccf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:keyboard-16-solid" /></template>
