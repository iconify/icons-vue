<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caevd78ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="caevd78ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:folder" /></template>
