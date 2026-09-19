<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7er9jb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7er9jb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bloom" /></template>
