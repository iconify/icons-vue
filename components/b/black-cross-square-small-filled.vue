<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7pr7mgam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="i7pr7mgam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-cross-square-small-filled" /></template>
