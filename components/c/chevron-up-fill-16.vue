<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsuw80_8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hsuw80_8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-up-fill-16" /></template>
