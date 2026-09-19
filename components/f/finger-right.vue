<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo382tbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo382tbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-right" /></template>
