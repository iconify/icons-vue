<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu4d_7b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nu4d_7b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-right-simple-fill" /></template>
