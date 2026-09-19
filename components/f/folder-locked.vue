<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5xis_zfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n5xis_zfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-locked" /></template>
