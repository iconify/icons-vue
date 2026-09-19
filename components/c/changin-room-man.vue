<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brs0dzbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brs0dzbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:changin-room-man" /></template>
