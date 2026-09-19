<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uet2whbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uet2whbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-polygon" /></template>
