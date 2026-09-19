<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgc7y8xwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgc7y8xwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:insert-before" /></template>
