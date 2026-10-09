<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uczxtfbti.css';
import '../../css/p/p1cx38bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uczxtfbti"/><path class="p1cx38bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chef-hat-20" /></template>
