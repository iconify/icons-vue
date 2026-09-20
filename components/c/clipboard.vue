<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itdl9g46c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itdl9g46c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:clipboard" /></template>
