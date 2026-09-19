<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojhnb-a7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojhnb-a7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:eslint" /></template>
