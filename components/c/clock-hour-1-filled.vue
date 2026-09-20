<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpl6ieb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpl6ieb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-1-filled" /></template>
