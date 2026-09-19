<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns55xbbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ns55xbbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:film-fill" /></template>
