<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh1wx-cjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh1wx-cjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-boolean-solid" /></template>
