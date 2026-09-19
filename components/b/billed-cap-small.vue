<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqjjdx6vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hqjjdx6vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:billed-cap-small" /></template>
