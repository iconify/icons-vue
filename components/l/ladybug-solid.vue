<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxn-31-fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oxn-31-fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:ladybug-solid" /></template>
