<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh823tkng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":77,"height":729};
const content = `<path class="gh823tkng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:exclam" /></template>
