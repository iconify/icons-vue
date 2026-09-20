<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-1f9yqij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-1f9yqij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:firewalla" /></template>
