<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c10vmihzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":438,"height":512};
const content = `<path class="c10vmihzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fossa" /></template>
