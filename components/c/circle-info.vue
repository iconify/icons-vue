<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4i81-f_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v4i81-f_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-info" /></template>
