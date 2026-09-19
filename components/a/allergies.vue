<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmp39m8qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jmp39m8qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:allergies" /></template>
