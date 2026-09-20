<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6khx287g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6khx287g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-check" /></template>
