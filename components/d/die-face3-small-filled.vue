<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7g9menyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o7g9menyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face3-small-filled" /></template>
