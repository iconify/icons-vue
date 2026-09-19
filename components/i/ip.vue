<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l99px9b1j.css';
import '../../css/z/zhugi-b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l99px9b1j"/><path class="zhugi-b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:ip" /></template>
