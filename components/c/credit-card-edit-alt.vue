<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqdrr6ohb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqdrr6ohb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-edit-alt" /></template>
