<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha2ibjb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ha2ibjb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-above-outstretched-hand" /></template>
