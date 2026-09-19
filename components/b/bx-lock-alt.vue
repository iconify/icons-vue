<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t33jnj4eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t33jnj4eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-lock-alt" /></template>
