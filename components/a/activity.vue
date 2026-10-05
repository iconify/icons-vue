<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1-idl2gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1-idl2gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:activity" /></template>
