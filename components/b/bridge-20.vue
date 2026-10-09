<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1t5mtm0a.css';
import '../../css/w/w1gklacoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n1t5mtm0a"/><path class="w1gklacoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bridge-20" /></template>
