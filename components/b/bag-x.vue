<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxhk0c9bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxhk0c9bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-x" /></template>
