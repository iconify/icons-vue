<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_-pb6bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_-pb6bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:eye-off" /></template>
