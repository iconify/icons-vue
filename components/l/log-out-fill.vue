<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb8a3tzeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb8a3tzeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:log-out-fill" /></template>
