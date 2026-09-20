<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfr9e0tvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dfr9e0tvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folders-outline" /></template>
