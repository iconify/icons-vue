<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmwx09b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmwx09b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fireworks" /></template>
