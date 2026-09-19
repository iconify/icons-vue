<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_lwrw-gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c_lwrw-gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:book" /></template>
