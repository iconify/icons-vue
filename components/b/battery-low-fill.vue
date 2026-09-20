<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu-0ao1so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qu-0ao1so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:battery-low-fill" /></template>
