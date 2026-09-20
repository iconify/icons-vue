<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3___fhtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="b3___fhtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:composition-oval" /></template>
