<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgqj3z6yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgqj3z6yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bitly" /></template>
