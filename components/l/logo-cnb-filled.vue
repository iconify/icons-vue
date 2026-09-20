<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp7c32rjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp7c32rjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-cnb-filled" /></template>
