<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0guk_b0a.css';
import '../../css/c/citsypb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0guk_b0a"/><path class="citsypb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-top-arrow-filled" /></template>
