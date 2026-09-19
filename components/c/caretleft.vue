<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjp4mac5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":9,"height":16};
const content = `<path class="pjp4mac5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:caretleft" /></template>
