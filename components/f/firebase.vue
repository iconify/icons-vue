<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7w1k3b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7w1k3b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:firebase" /></template>
