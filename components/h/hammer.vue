<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbr31wqfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbr31wqfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hammer" /></template>
