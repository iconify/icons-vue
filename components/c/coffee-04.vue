<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymwnz6xdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymwnz6xdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:coffee-04" /></template>
