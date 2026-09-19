<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa-qvu2lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sa-qvu2lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-pause-fill" /></template>
