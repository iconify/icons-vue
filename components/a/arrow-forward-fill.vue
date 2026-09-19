<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqg0evtvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqg0evtvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-forward-fill" /></template>
