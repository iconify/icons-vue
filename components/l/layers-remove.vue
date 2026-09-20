<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylaybdqkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylaybdqkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:layers-remove" /></template>
