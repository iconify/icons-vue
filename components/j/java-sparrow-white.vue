<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na54l-b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="na54l-b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:java-sparrow-white" /></template>
