<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od84yrbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="od84yrbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:javascript-solid" /></template>
