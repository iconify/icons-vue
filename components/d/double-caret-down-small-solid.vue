<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo-1i0jab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="yo-1i0jab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-down-small-solid" /></template>
