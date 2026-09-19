<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw8w66t8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="aw8w66t8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:filmstrip" /></template>
