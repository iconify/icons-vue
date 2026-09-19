<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9gpoj-sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c9gpoj-sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keyboard-filled" /></template>
