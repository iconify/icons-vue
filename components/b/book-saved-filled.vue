<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqv5sccyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqv5sccyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:book-saved-filled" /></template>
