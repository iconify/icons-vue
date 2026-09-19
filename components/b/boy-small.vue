<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gld0fn8un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gld0fn8un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:boy-small" /></template>
