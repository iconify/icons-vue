<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkryll1rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkryll1rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:accesible-restroom" /></template>
