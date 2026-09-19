<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5bk4c3ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h5bk4c3ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:house-fill" /></template>
