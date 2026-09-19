<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz6foib1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iz6foib1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:check-16-solid" /></template>
