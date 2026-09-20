<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f510iwbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-3.5};
const content = `<path class="f510iwbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:eggs" /></template>
