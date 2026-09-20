<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6on6gbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z6on6gbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-inner-solid" /></template>
