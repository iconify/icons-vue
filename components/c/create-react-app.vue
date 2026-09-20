<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skz7itc8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skz7itc8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:create-react-app" /></template>
