<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px0eocvtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="px0eocvtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-sun-with-rays-small" /></template>
