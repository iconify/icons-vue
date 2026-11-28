<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jougr8fnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jougr8fnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gem-solid" /></template>
