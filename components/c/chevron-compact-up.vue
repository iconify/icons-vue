<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy71kdb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dy71kdb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-compact-up" /></template>
