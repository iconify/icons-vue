<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic7cpcbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ic7cpcbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:liver" /></template>
