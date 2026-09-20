<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni68l2f_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni68l2f_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:keypad-fill" /></template>
