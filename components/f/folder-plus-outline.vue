<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebspqb8ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ebspqb8ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-plus-outline" /></template>
