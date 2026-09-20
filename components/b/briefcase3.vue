<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfwlttb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jfwlttb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:briefcase3" /></template>
