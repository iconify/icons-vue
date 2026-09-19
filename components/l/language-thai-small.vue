<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgkwoabeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pgkwoabeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-thai-small" /></template>
