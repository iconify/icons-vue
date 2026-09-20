<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyj8jf1aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="fyj8jf1aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:alien-solid" /></template>
