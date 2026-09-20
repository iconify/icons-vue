<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg_gupbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jg_gupbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bootstrap" /></template>
