<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn6axibue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn6axibue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-12" /></template>
