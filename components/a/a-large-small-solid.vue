<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukdrheb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukdrheb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:a-large-small-solid" /></template>
