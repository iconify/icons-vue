<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvoy5jbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pvoy5jbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:colors-filled" /></template>
