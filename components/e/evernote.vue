<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8hg_bbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8hg_bbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:evernote" /></template>
