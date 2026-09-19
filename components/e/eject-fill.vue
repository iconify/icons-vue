<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7w7vgbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u7w7vgbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:eject-fill" /></template>
