<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei8oxrlci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei8oxrlci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:arrow-up-right" /></template>
