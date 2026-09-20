<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nui8jr4nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nui8jr4nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:broom" /></template>
