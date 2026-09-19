<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr2o12b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vr2o12b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:copies-small" /></template>
