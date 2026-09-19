<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgmo-zb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgmo-zb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-coffee-togo" /></template>
