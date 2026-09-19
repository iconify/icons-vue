<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijigewbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijigewbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:lock-unlock" /></template>
