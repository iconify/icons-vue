<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-b3v2tyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g-b3v2tyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:crescent-moon-small-filled" /></template>
