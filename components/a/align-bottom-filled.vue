<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7nhw4buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f7nhw4buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-bottom-filled" /></template>
