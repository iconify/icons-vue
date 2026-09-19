<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2x8iab1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2x8iab1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:comment-plus-solid" /></template>
