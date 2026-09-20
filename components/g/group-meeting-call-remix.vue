<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzc1c8a6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bzc1c8a6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:group-meeting-call-remix" /></template>
