<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8kn_3bny.css';
import '../../css/f/fn8q6tmlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8kn_3bny"/><path class="fn8q6tmlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:desktop-light" /></template>
