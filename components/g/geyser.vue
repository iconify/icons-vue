<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn5t7vble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kn5t7vble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:geyser" /></template>
