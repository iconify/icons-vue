<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysitrub7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysitrub7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:eject-solid" /></template>
