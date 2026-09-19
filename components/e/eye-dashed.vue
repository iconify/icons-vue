<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxn8mjf9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qxn8mjf9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:eye-dashed" /></template>
