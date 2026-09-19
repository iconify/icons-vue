<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixj9blbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ixj9blbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bell-snooze-16-solid" /></template>
