<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz132_0hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz132_0hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hostinger" /></template>
