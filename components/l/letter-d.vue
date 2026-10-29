<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmmbqcype.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmmbqcype"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-d" /></template>
