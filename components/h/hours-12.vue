<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eavl5i9ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eavl5i9ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hours-12" /></template>
