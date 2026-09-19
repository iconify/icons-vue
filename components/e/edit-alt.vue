<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab6ek4sun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab6ek4sun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:edit-alt" /></template>
