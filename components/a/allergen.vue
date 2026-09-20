<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnk5g35xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnk5g35xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:allergen" /></template>
