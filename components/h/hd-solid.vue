<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy8o4rbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy8o4rbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hd-solid" /></template>
