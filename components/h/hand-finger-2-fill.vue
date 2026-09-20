<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jijy0rbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jijy0rbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-finger-2-fill" /></template>
