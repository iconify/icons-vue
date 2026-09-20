<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3bvu71xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g3bvu71xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:capacitor-16" /></template>
