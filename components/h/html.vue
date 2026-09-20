<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-ez5do3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="b-ez5do3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:html" /></template>
