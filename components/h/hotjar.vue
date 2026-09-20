<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe_jndb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe_jndb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hotjar" /></template>
