<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6t4d8u5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n6t4d8u5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:filter-small" /></template>
