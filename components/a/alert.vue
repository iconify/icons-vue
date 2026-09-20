<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz6mg5zcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="bz6mg5zcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:alert" /></template>
