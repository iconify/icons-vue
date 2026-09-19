<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9eomtbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b9eomtbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-right-double-triangle-with-vertical-bar-filled" /></template>
