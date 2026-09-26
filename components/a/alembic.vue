<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-3igr9gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m-3igr9gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:alembic" /></template>
