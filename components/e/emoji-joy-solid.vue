<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov5bo0d0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ov5bo0d0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:emoji-joy-solid" /></template>
