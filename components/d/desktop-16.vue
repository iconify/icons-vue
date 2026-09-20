<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekuwo8vtc.css';
import '../../css/a/a5pezv9ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ekuwo8vtc"/><path clip-rule="evenodd" class="a5pezv9ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:desktop-16" /></template>
