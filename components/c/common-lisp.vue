<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omojj5bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omojj5bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:common-lisp" /></template>
