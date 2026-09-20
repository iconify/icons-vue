<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c210f-7ji.css';
import '../../css/i/i9l7_bcpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="c210f-7ji"/><path class="i9l7_bcpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:labor-delivery" /></template>
