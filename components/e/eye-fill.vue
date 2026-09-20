<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz3_bd5iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qz3_bd5iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:eye-fill" /></template>
