<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi0a_4boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="yi0a_4boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:businesscardalt" /></template>
