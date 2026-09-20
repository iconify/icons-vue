<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5hpl9csu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5hpl9csu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:less-than-or-equal" /></template>
