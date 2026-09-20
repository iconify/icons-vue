<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itm4kqbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itm4kqbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:comment-plus-filled" /></template>
