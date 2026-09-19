<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky3hg7kgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ky3hg7kgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:kusto" /></template>
