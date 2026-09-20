<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htu_6ab6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="htu_6ab6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:adjust-vertical-alt-solid" /></template>
