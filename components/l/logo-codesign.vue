<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgjrhnbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgjrhnbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-codesign" /></template>
