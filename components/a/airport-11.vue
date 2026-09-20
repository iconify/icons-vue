<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2od65-nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="v2od65-nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:airport-11" /></template>
