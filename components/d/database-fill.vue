<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv821zr0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yv821zr0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:database-fill" /></template>
