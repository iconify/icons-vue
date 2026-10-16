<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar3qoibyd.css';
import '../../css/r/rtsvhsn1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ar3qoibyd"/><path class="rtsvhsn1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hacksaw-48-bold" /></template>
