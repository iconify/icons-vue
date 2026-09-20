<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgb68_bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lgb68_bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-laptop" /></template>
