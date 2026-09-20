<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi9pucb8a.css';
import '../../css/s/s08qpzh5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi9pucb8a"/><path clip-rule="evenodd" class="s08qpzh5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:gif" /></template>
