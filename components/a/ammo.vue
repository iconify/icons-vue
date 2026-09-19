<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmnn-r53m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmnn-r53m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ammo" /></template>
