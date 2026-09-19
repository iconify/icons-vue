<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_9idcc2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p_9idcc2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-up-fill-16" /></template>
