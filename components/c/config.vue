<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gscn4tkwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gscn4tkwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:config" /></template>
