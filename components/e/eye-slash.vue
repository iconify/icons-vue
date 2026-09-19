<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el9pnwe6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el9pnwe6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:eye-slash" /></template>
