<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwo8fybtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dwo8fybtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:apple-filled" /></template>
