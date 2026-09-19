<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pndwf3b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pndwf3b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:chevrons-up-wide" /></template>
