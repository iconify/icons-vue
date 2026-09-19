<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y20fa_bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y20fa_bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:emojisurprise" /></template>
