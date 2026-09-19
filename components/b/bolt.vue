<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aflt1xbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aflt1xbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:bolt" /></template>
