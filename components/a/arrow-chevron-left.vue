<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx2s8s6gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fx2s8s6gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-chevron-left" /></template>
