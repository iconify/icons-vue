<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t52p9_bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t52p9_bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:basket-alt-light" /></template>
