<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7idm8bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7idm8bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forbidden-circle-outline" /></template>
