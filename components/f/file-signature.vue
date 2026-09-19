<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjqdud4ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vjqdud4ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-signature" /></template>
