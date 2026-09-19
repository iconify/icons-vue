<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3k5x5h4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r3k5x5h4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrows-expand" /></template>
