<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tudti3b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tudti3b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ball-basket-filled" /></template>
