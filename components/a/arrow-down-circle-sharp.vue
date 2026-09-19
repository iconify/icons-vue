<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4-0o5epi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h4-0o5epi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-down-circle-sharp" /></template>
