<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-mdp1bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="l-mdp1bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:atm" /></template>
