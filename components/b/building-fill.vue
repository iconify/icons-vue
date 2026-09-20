<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr2exacnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wr2exacnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:building-fill" /></template>
