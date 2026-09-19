<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm7dj77gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cm7dj77gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:delete" /></template>
