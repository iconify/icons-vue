<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf2h6wznc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kf2h6wznc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:github-fill-24" /></template>
