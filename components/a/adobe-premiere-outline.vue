<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0vn8x9rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0vn8x9rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:adobe-premiere-outline" /></template>
