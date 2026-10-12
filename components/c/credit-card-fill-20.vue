<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imywpub2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="imywpub2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:credit-card-fill-20" /></template>
