<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_b06wvdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c_b06wvdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-gabled-shelter-with-fireplace-and-chimney" /></template>
