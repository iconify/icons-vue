<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj7fhcc0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dj7fhcc0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleleft" /></template>
