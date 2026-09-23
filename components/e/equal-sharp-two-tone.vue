<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shqdbd5id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shqdbd5id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:equal-sharp-two-tone" /></template>
