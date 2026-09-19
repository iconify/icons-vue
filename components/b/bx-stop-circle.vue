<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqbkv8u2i.css';
import '../../css/s/s9lfmybtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="s9lfmybtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-stop-circle" /></template>
