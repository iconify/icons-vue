<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmyhv4bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="kmyhv4bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-turn-up-left" /></template>
