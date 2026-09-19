<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0254uoqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":448};
const content = `<path class="g0254uoqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:gamepad" /></template>
