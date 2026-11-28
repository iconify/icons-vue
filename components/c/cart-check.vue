<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hijugpbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hijugpbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cart-check" /></template>
