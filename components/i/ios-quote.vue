<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb0uyplao.css';
import '../../css/v/volv26bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bb0uyplao"/><path class="volv26bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-quote" /></template>
