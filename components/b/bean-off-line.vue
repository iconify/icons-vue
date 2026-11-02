<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb7kxrpge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb7kxrpge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bean-off-line" /></template>
