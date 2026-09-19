<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmu8-9b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="gmu8-9b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file-image" /></template>
