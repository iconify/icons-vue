<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rthtgrrbd.css';
import '../../css/r/rbqngdcgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rthtgrrbd"/><path class="rbqngdcgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-48" /></template>
