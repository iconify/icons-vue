<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wskhgyk4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wskhgyk4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:c-outline" /></template>
