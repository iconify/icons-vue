<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs9_k7rdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs9_k7rdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-add-thin" /></template>
