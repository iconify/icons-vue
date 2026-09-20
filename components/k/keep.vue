<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5n0-rb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5n0-rb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:keep" /></template>
