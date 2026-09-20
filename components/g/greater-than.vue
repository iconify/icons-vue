<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bze682cdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bze682cdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:greater-than" /></template>
