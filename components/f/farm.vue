<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sasqfv1ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sasqfv1ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:farm" /></template>
