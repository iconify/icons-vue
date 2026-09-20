<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx1---vpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2};
const content = `<path class="fx1---vpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:cutlery-f" /></template>
