<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du55pnb9m.css';
import '../../css/o/od1iqpboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="du55pnb9m"/><path class="od1iqpboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:image-layout-thumbnail" /></template>
