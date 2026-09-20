<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw7dlv7vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw7dlv7vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:houdini" /></template>
