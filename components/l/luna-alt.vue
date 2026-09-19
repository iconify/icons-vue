<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhi3qacmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhi3qacmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:luna-alt" /></template>
