<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bznvht37f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bznvht37f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:car-sharp" /></template>
