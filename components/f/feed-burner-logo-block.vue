<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku-880b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ku-880b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:feed-burner-logo-block" /></template>
