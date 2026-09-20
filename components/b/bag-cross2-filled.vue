<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si_qkgb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si_qkgb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-cross2-filled" /></template>
