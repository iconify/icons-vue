<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4dpjs72k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m4dpjs72k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:girl-small-filled" /></template>
