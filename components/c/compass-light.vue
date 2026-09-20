<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiaq27v-e.css';
import '../../css/b/b0rftsbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiaq27v-e"/><path class="b0rftsbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:compass-light" /></template>
