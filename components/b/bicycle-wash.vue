<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k49hg70lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k49hg70lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bicycle-wash" /></template>
