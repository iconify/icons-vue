<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9oso9ufg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9oso9ufg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:hashtag-solid" /></template>
