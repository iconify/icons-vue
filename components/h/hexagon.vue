<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcg03cc8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcg03cc8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:hexagon" /></template>
