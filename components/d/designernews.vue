<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqeoo9ppw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqeoo9ppw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:designernews" /></template>
