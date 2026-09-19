<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r68vbdzvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r68vbdzvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:command-line-solid" /></template>
