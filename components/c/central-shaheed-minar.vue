<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx0fi0t2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx0fi0t2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:central-shaheed-minar" /></template>
