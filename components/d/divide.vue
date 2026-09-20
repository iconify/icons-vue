<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csj82-bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csj82-bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:divide" /></template>
