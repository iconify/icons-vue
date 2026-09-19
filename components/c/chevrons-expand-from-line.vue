<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muiyoab3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="muiyoab3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:chevrons-expand-from-line" /></template>
