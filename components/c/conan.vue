<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmlvw01bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":481,"height":512};
const content = `<path class="xmlvw01bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:conan" /></template>
