<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9z93jo_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k9z93jo_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:caret-down" /></template>
