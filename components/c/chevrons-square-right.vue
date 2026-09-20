<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiaz00bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="xiaz00bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-square-right" /></template>
