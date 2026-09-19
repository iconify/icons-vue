<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp06m64up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cp06m64up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-uturn-cw-left" /></template>
