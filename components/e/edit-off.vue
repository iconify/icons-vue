<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9d6ei8sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y9d6ei8sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:edit-off" /></template>
