<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjsgojboe.css';
import '../../css/f/f11gmybah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sjsgojboe"/><path class="f11gmybah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-empty-48-bold" /></template>
