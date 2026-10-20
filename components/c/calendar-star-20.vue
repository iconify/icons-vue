<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti4_udjxz.css';
import '../../css/a/af6s1vcxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ti4_udjxz"/><path class="af6s1vcxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-star-20" /></template>
