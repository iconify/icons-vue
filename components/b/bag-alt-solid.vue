<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgrd1mbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qgrd1mbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bag-alt-solid" /></template>
