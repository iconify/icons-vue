<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqtmz3b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fqtmz3b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-left-simple-fill" /></template>
