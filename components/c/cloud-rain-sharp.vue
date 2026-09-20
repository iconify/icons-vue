<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywwwdhwxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywwwdhwxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-sharp" /></template>
