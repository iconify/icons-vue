<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qncigyyhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qncigyyhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:floppy-disk-16-solid" /></template>
