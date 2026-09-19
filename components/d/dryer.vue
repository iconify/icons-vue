<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnpzzt4xm.css';
import '../../css/h/hcvvkpbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnpzzt4xm"/><path class="hcvvkpbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dryer" /></template>
