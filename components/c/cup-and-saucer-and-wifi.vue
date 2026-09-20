<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxxj6fbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dxxj6fbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cup-and-saucer-and-wifi" /></template>
