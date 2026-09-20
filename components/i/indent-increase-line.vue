<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-b_krv-u.css';
import '../../css/z/zs61z1u9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-b_krv-u"/><path class="zs61z1u9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:indent-increase-line" /></template>
