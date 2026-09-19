<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbv0mj7_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="tbv0mj7_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-upload" /></template>
