<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8ah_jb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8ah_jb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:magic-wand-off-filled" /></template>
