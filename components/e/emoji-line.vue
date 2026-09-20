<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-e_8qbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-e_8qbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:emoji-line" /></template>
