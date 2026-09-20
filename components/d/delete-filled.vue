<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v09mmk0wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v09mmk0wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:delete-filled" /></template>
