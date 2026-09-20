<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjuw0mb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjuw0mb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:forgejo" /></template>
