<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpmq2cbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hpmq2cbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ec" /></template>
