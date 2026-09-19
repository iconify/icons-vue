<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckulpe9ec.css';
import '../../css/h/h_2ddrein.css';
import '../../css/f/fa_16t6kl.css';
import '../../css/b/bs-dfccax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckulpe9ec"/><path class="h_2ddrein"/><circle class="fa_16t6kl"/><path class="bs-dfccax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:linkedin" /></template>
