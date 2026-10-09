<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtvm8qbid.css';
import '../../css/n/n1vzbldsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtvm8qbid"/><path class="n1vzbldsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrows-horizontal-48-bold" /></template>
