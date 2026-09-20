<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul6ql98hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul6ql98hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:anvil" /></template>
