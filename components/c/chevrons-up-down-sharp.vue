<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivzo09bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivzo09bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-up-down-sharp" /></template>
