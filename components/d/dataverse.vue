<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1u67tbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="b1u67tbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:dataverse" /></template>
