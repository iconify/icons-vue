<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0r4fir6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b0r4fir6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-settings-2" /></template>
