<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6fqnxbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6fqnxbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:equal-not-sharp-two-tone" /></template>
