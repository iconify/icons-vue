<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcj5b4bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pcj5b4bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:anja-outline" /></template>
