<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_uzvwaql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="y_uzvwaql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad-up-left-fill" /></template>
