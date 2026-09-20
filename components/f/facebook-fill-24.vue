<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gahg-u41y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gahg-u41y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:facebook-fill-24" /></template>
