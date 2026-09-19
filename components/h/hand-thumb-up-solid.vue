<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmgrhxbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmgrhxbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-thumb-up-solid" /></template>
