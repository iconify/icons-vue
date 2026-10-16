<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwsn-fblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uwsn-fblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:harmonics-48-bold" /></template>
