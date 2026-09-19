<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5y806bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s5y806bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-minus" /></template>
