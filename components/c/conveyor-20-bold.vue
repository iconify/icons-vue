<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kekwewb2q.css';
import '../../css/a/a52o52b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kekwewb2q"/><path class="a52o52b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:conveyor-20-bold" /></template>
