<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv035x6ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kv035x6ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:grinning-face-with-star-eyes" /></template>
