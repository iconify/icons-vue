<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq5--8b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zq5--8b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-down-solid" /></template>
