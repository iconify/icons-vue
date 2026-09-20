<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txyzud7jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txyzud7jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cloudflare" /></template>
