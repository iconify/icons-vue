<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob01ca7jx.css';
import '../../css/f/f_4nudb1i.css';
import '../../css/n/nzv-bubbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ob01ca7jx"/><path class="f_4nudb1i"/><path class="nzv-bubbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desertification-20-bold" /></template>
