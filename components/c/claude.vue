<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkphsvb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkphsvb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:claude" /></template>
