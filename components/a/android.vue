<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe1_3nbpy.css';
import '../../css/g/ga0a0lbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":54,"height":100};
const content = `<path class="xe1_3nbpy"/><path class="ga0a0lbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:android" /></template>
