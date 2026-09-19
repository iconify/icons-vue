<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbg72rhcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xbg72rhcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:dinner" /></template>
