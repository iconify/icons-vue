<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_jlntbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_jlntbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-moon" /></template>
