<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v__un6b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v__un6b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:checklist-16" /></template>
