<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkvpl8bch.css';
import '../../css/j/j6h96-z2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkvpl8bch"/><path class="j6h96-z2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chat-add-24" /></template>
