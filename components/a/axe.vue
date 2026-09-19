<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/got2f-y_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="got2f-y_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:axe" /></template>
