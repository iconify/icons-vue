<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oubr6vbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oubr6vbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hand-held" /></template>
