<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp-tcp6en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp-tcp6en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gas" /></template>
