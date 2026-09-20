<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpi3gdb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpi3gdb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-cancel-outline" /></template>
