<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu_p-r0dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu_p-r0dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:helmet" /></template>
