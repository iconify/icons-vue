<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhikjhb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nhikjhb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:expand-left-and-right" /></template>
