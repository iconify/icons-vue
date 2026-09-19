<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g712bfbaj.css';
import '../../css/h/hy4qzjznx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g712bfbaj"/><path class="hy4qzjznx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-alt" /></template>
