<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb-7nfbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-7nfbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:filter-light" /></template>
