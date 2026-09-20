<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opp0eqbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opp0eqbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:envato" /></template>
