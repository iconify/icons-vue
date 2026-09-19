<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecs7db2qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ecs7db2qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file-powerpoint" /></template>
