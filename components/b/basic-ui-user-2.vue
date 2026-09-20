<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et0aa-ggi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="et0aa-ggi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-user-2" /></template>
