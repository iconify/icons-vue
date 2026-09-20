<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw_nd3bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw_nd3bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:keyboard-1" /></template>
