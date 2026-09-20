<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-jwpob4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a-jwpob4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:buss" /></template>
