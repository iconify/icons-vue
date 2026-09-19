<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0y859buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f0y859buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:clipboard-small-filled" /></template>
