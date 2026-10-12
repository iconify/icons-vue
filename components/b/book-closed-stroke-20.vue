<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aals9abum.css';
import '../../css/m/mz-fxr5ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aals9abum"/><path class="mz-fxr5ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-closed-stroke-20" /></template>
