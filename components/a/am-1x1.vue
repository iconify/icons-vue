<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-v7pcchz.css';
import '../../css/j/j-g4lup5t.css';
import '../../css/m/m7z06s_0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t-v7pcchz"/><path class="j-g4lup5t"/><path class="m7z06s_0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:am-1x1" /></template>
