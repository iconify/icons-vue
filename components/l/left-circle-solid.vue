<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z16gh80jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z16gh80jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:left-circle-solid" /></template>
