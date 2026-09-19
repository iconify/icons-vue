<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-rwddbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d-rwddbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:add-sharp" /></template>
