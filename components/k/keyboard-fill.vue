<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txw99oo3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txw99oo3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:keyboard-fill" /></template>
