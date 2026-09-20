<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epcos0d9j.css';
import '../../css/o/ocymuzb7a.css';
import '../../css/x/x6uuzdbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="epcos0d9j"/><path class="ocymuzb7a"/><path class="x6uuzdbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-tablet" /></template>
