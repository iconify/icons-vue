<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9i0_1j9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l9i0_1j9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:help-circle" /></template>
