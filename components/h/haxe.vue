<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrx6w39zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrx6w39zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:haxe" /></template>
