<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avw7vcbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="avw7vcbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:handshake" /></template>
