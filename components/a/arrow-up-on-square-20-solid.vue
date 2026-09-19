<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aod6y7ztn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="aod6y7ztn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-on-square-20-solid" /></template>
