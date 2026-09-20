<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsb_3sb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tsb_3sb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:lock-filled" /></template>
