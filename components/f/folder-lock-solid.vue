<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihxx5g--v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihxx5g--v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-lock-solid" /></template>
