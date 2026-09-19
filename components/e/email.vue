<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu6t8ibbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":750};
const content = `<path class="qu6t8ibbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:email" /></template>
