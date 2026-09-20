<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujwr_lkax.css';
import '../../css/c/c7cgn4zwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujwr_lkax"/><path class="c7cgn4zwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cloud-arrow-up" /></template>
