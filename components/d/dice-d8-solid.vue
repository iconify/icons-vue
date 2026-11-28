<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qupa7dizo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qupa7dizo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dice-d8-solid" /></template>
