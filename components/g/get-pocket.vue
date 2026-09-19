<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knp2qb6bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="knp2qb6bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:get-pocket" /></template>
