<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-kbjab1h.css';
import '../../css/m/m95s5yi8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-kbjab1h"/><path class="m95s5yi8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:face-alt-3" /></template>
