<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bffeugi-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bffeugi-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:app-store-filled" /></template>
