<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlz6nfoqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tlz6nfoqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-2-filled" /></template>
