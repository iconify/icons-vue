<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfccs038u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qfccs038u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:joypad" /></template>
