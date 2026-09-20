<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqb4xlb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gqb4xlb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gameboy-bold" /></template>
