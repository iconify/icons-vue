<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvg-drbfm.css';
import '../../css/f/f0fgz2b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dvg-drbfm"/><path class="f0fgz2b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:api-20-bold" /></template>
