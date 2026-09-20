<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd4yuk13a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="fd4yuk13a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:art-gallery-11" /></template>
