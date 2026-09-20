<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz3ozkfdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz3ozkfdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-minus" /></template>
