<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt8069bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt8069bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:alot" /></template>
