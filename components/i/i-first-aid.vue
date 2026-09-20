<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbvkmbbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="bbvkmbbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-first-aid" /></template>
