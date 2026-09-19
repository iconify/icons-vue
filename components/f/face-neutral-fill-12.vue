<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cedh__b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cedh__b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-neutral-fill-12" /></template>
