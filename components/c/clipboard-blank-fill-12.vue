<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmb67ktsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mmb67ktsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-blank-fill-12" /></template>
