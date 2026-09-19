<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1cg0o4-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1cg0o4-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-cancel" /></template>
