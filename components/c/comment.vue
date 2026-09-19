<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8xlj6v0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8xlj6v0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:comment" /></template>
