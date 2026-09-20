<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja7-tfbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ja7-tfbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:fingerprint-solid" /></template>
