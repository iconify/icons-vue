<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8u4nj3lr.css';
import '../../css/l/lv7a0p21m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8u4nj3lr"/><path class="lv7a0p21m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-folder-minus" /></template>
