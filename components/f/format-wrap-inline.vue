<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9aox44tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9aox44tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-wrap-inline" /></template>
