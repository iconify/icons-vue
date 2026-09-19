<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k20krjj8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="k20krjj8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hanger" /></template>
