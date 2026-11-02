<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whzzz92ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whzzz92ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dice-3-fill" /></template>
