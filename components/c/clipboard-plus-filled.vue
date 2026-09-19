<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l17hfdciu.css';
import '../../css/l/lnshn9kak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l17hfdciu"/><path class="lnshn9kak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clipboard-plus-filled" /></template>
