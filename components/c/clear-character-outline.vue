<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvn5f30vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvn5f30vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:clear-character-outline" /></template>
