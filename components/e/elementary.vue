<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze9gskg2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze9gskg2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:elementary" /></template>
