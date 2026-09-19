<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq8haq6el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cq8haq6el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:contrast-sharp" /></template>
