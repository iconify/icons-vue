<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7vpdnbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c7vpdnbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:lastfm-logo-block" /></template>
