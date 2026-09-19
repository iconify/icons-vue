<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5-cfxoyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5-cfxoyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:airplane" /></template>
