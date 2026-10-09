<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y04gfnbxb.css';
import '../../css/t/t170-qrdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y04gfnbxb"/><path class="t170-qrdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-20" /></template>
