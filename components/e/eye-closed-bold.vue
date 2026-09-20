<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz-3upcrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jz-3upcrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-closed-bold" /></template>
