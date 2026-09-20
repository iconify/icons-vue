<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnnzl5bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnnzl5bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:mail-fill" /></template>
