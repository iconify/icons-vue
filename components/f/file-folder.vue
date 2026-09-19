<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t26jdnbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t26jdnbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-folder" /></template>
