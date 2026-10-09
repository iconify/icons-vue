<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he122gpwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="he122gpwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:link-off-48" /></template>
