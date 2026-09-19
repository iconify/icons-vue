<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2otw27pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2otw27pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:clock-solid" /></template>
