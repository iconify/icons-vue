<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k93f81brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="k93f81brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-latin-small-filled" /></template>
