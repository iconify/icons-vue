<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy0fe28yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wy0fe28yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-previous-solid" /></template>
