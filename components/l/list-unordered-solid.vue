<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi442-b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="zi442-b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:list-unordered-solid" /></template>
