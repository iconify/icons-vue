<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urtzmgbhs.css';
import '../../css/q/q5rhorqnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="urtzmgbhs"/><path class="q5rhorqnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:eye-off-outline" /></template>
