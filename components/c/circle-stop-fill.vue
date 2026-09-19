<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kma08ubea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kma08ubea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-stop-fill" /></template>
