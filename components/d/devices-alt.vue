<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csjodqbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csjodqbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:devices-alt" /></template>
