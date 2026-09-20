<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogh1vxbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ogh1vxbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:euro-solid" /></template>
