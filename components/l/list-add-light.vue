<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qehc4-_kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qehc4-_kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:list-add-light" /></template>
