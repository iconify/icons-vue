<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxx4uub5u.css';
import '../../css/m/m7s1g-b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxx4uub5u"/><path class="m7s1g-b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:at" /></template>
