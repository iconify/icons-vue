<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev036wt0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev036wt0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googletv" /></template>
