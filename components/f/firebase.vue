<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4v9t8bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4v9t8bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:firebase" /></template>
