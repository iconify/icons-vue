<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h17i68bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h17i68bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gravit-designer" /></template>
