<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m65wjx7pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m65wjx7pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codenewbie" /></template>
