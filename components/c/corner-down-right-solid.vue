<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r21elibcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r21elibcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-down-right-solid" /></template>
