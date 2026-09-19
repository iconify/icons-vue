<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h__5z1bbd.css';
import '../../css/s/s2rt5pbav.css';
import '../../css/z/zv3nb1bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h__5z1bbd"/><path class="s2rt5pbav"/><path class="zv3nb1bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:backpack-filled" /></template>
