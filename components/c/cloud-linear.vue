<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdzwvjzpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdzwvjzpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-linear" /></template>
