<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1vnqjkpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o1vnqjkpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:checkmark-circled-small" /></template>
