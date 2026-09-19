<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuzco31ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zuzco31ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:folder-open" /></template>
