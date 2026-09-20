<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrrw9kgyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrrw9kgyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:basket-alt" /></template>
