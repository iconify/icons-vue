<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0s51ebnl.css';
import '../../css/p/pzvbzhw1c.css';
import '../../css/z/z-_-ey0ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z0s51ebnl"/><path class="pzvbzhw1c"/><path class="z-_-ey0ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:datetime" /></template>
