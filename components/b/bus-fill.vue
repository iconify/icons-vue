<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8ywu5bta.css';
import '../../css/s/s776ws_jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8ywu5bta"/><path clip-rule="evenodd" class="s776ws_jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:bus-fill" /></template>
