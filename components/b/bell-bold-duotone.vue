<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8czseb2v.css';
import '../../css/e/e_ax9fbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8czseb2v"/><path class="e_ax9fbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-bold-duotone" /></template>
