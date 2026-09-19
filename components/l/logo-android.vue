<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwdicc8xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xwdicc8xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-android" /></template>
