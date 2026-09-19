<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he7habbvj.css';
import '../../css/f/f358-er9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he7habbvj"/><path class="f358-er9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:building-house" /></template>
