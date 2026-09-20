<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7fr3obbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7fr3obbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-down-left-light" /></template>
