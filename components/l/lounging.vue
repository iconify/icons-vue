<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic9-wxsjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ic9-wxsjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:lounging" /></template>
