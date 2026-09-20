<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7kzzzk4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k7kzzzk4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:casino" /></template>
