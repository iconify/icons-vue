<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su9k-ubgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su9k-ubgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bastyon" /></template>
