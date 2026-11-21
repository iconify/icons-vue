<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bem5i2brp.css';
import '../../css/q/qjzeox4ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bem5i2brp"/><path class="qjzeox4ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ice-cream-outline" /></template>
