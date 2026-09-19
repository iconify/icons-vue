<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro7j6o5qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ro7j6o5qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-elbow-right-up" /></template>
