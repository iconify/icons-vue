<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vie3v6bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vie3v6bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-ghost-filled" /></template>
