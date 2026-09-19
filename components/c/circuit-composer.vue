<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhvfzxc8c.css';
import '../../css/k/km4pjabfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rhvfzxc8c"/><path class="km4pjabfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:circuit-composer" /></template>
