<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqz_3cskk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqz_3cskk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bell-off" /></template>
