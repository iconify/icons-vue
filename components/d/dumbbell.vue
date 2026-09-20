<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r60vhccip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r60vhccip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dumbbell" /></template>
