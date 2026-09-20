<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bibpq4bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bibpq4bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bmcsoftware" /></template>
