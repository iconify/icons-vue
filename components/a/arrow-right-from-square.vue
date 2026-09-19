<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0f7br4-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f0f7br4-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-right-from-square" /></template>
