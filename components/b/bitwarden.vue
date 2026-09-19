<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boh2k7bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boh2k7bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bitwarden" /></template>
