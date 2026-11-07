<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0-gkacxy.css';
import '../../css/y/yxn4dklvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0-gkacxy"/><path class="yxn4dklvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folders-bold" /></template>
