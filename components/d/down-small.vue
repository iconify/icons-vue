<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g78b70bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g78b70bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:down-small" /></template>
