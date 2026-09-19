<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r59x8o_6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r59x8o_6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:folders" /></template>
