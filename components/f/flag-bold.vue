<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itn0mccsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itn0mccsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flag-bold" /></template>
