<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhyge19vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhyge19vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:adjust-circle" /></template>
