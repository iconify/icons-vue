<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yklz2q6fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yklz2q6fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-check" /></template>
