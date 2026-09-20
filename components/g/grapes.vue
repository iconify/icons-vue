<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl6-vpbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nl6-vpbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:grapes" /></template>
