<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmlz9acfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cmlz9acfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:falcon" /></template>
