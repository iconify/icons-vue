<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq59b2bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uq59b2bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:floppy-disk-filled" /></template>
