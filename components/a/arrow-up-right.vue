<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhq9u8zqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nhq9u8zqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-up-right" /></template>
