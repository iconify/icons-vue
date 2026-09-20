<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z73vgbbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z73vgbbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:check-circle-dashed" /></template>
