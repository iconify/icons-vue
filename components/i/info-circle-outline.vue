<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upv0h93hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="upv0h93hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:info-circle-outline" /></template>
