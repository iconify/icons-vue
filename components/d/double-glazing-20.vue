<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny1ct12zc.css';
import '../../css/e/e--yctl3q.css';
import '../../css/c/cynz-yk1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ny1ct12zc"/><path class="e--yctl3q"/><path class="cynz-yk1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:double-glazing-20" /></template>
