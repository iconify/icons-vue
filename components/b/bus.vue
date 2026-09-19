<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyojb603r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dyojb603r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bus" /></template>
