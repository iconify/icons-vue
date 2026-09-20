<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/styafgb6l.css';
import '../../css/h/ht6h5ebzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="styafgb6l"/><path clip-rule="evenodd" class="ht6h5ebzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-date-light" /></template>
