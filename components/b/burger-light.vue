<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biljftzdn.css';
import '../../css/s/s4-6ofb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biljftzdn"/><path clip-rule="evenodd" class="s4-6ofb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:burger-light" /></template>
