<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo9--sbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jo9--sbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:cancel" /></template>
