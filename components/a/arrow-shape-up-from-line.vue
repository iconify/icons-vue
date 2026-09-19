<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iin1znbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iin1znbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-up-from-line" /></template>
