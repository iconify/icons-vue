<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4qou-b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h4qou-b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:face-robot" /></template>
