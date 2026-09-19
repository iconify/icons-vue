<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuj6gbcwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cuj6gbcwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:ban-dashed" /></template>
