<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5fxn4-5j.css';
import '../../css/i/i6jfppbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i5fxn4-5j"/><path class="i6jfppbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-fastlane" /></template>
