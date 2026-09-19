<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmgw7nb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmgw7nb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bracket" /></template>
