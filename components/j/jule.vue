<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3bsu7bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n3bsu7bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jule" /></template>
