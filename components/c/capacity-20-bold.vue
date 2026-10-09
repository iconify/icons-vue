<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiabdabxj.css';
import '../../css/z/z_3gq8xqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wiabdabxj"/><path class="z_3gq8xqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:capacity-20-bold" /></template>
