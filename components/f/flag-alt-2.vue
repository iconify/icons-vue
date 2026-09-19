<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygttbqbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygttbqbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flag-alt-2" /></template>
