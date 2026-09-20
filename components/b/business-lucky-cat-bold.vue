<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hupxt07cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hupxt07cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:business-lucky-cat-bold" /></template>
