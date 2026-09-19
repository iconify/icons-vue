<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx3wucg6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yx3wucg6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:evernote" /></template>
