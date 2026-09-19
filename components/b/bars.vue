<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qynsx1wxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qynsx1wxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:bars" /></template>
